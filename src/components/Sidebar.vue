<template>
  <div>
    <el-menu
        style="min-height: calc(100vh - 60px)"
        :uniqueOpened="true"
        default-active="2"
        class="el-menu-vertical-demo"
    >

      <el-menu-item index="0">
        <el-icon>
          <HomeFilled/>
        </el-icon>
        <template #title>首页</template>
      </el-menu-item>

      <el-sub-menu index="1">
        <template #title>
          <div>
            <el-icon>
              <Tickets/>
            </el-icon>
            <span>数据管理</span>
          </div>
        </template>
        <el-menu-item-group>
          <template #title>分组一</template>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-sub-menu>


      <el-sub-menu index="2">
        <template #title>
          <div>
            <el-icon>
              <Tickets/>
            </el-icon>
            <span>图标查看</span>
          </div>
        </template>
        <el-menu-item-group>
          <template #title>分组一</template>
          <el-menu-item index="2-1">选项1</el-menu-item>
          <el-menu-item index="2-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-sub-menu>


      <el-sub-menu index="3">
        <template #title>
          <div>
            <el-icon>
              <Tickets/>
            </el-icon>
            <span>设置</span>
          </div>
        </template>
        <el-menu-item-group>
          <template #title>分组一</template>
          <el-menu-item index="3-1">选项1</el-menu-item>
          <el-menu-item index="3-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-sub-menu>

      <el-sub-menu index="4">
        <template #title>
          <div>
            <el-icon>
              <Tickets/>
            </el-icon>
            <span>说明</span>
          </div>
        </template>
        <el-menu-item-group>
          <template #title>分组一</template>
          <el-menu-item index="3-1">选项1</el-menu-item>
          <el-menu-item index="3-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-sub-menu>

      <el-sub-menu index="5">
        <template #title>
          <div>
            <el-icon>
              <Tickets/>
            </el-icon>
            <span>关于</span>
          </div>
        </template>
        <el-menu-item-group>
          <template #title>分组一</template>
          <el-menu-item index="3-1">选项1</el-menu-item>
          <el-menu-item index="3-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-sub-menu>


    </el-menu>
  </div>
</template>

<script>
import {Tickets,Document, Menu, Location, Setting, HomeFilled} from '@element-plus/icons-vue'

export default {
  name: "Sidebar",
  components: {
    Document,
    Menu,
    Location,
    Setting,
    HomeFilled,
    Tickets
  }

}
</script>

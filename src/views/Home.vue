<template>
  <div class="home">
    <el-row>
      <el-col :span="10">
        <el-input placeholder="请输入课程" v-model="projectname"></el-input>
      </el-col>
      <el-col :span="2">
        <el-button type="primary"> 新增</el-button>
      </el-col>

    </el-row>
  </div>
</template>

<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'Home',
  setup () {
    const projectname = ref('')
    return {
      projectname
    }
  }
})
</script>

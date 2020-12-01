<template>
  <div class="home">
    <TodoForm/>
  </div>
</template>
<script>
import TodoForm from '@/components/TodoForm.vue'
export default {
  name: 'Home',
  components: {
    TodoForm
  }
}
</script>

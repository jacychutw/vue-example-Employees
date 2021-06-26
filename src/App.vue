<template>
  <div id="app">
    <InputForm />
    <DataTable />
  </div>
</template>

<script>
import InputForm from './components/InputForm.vue'
import DataTable from './components/DataTable.vue'

export default {
  name: 'App',
  components: {
    InputForm,
    DataTable
  }
}
</script>


  <template>
    <q-toolbar class="bg-primary text-white q-my-md shadow-2">
        <q-btn flat round dense icon="menu" class="q-mr-sm" />
        <q-separator dark vertical inset />
        <q-btn stretch flat label="HOME" to="/"/>
        <q-btn stretch flat label="Listar Clientes" to="/listar/clientes"/>
        <q-btn stretch flat label="Adicionar Cliente" to="/adicionar/cliente"/>

    </q-toolbar>
  </template>
<script>
export default {
    name: 'Header'
}

</script>

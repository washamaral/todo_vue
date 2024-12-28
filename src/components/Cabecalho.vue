<script setup>
const props = defineProps(['tarefasPendentes'])

</script>

<template>
    <header>
        <h1 class="p-5 mb-4 mt-4 bg-light rounded-3">Minhas tarefas</h1>
        <p>
            Você possui {{ props.tarefasPendentes }} tarefas pendentes
        </p>
    </header>
</template>
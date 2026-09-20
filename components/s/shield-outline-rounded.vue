<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnt5wibks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-outline-rounded" /></template>
<style>
.qnt5wibks {
  fill: currentColor;
  d: path("M11.714 20.817q-.15-.025-.282-.075q-2.951-1.125-4.691-3.816Q5 14.235 5 11.1V6.817q0-.514.293-.926q.292-.412.757-.597l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.464.186.757.597q.293.412.293.926V11.1q0 3.135-1.74 5.826t-4.692 3.816q-.131.05-.281.075t-.287.025t-.287-.025M12 19.9q2.6-.825 4.3-3.3t1.7-5.5V6.798q0-.192-.106-.346q-.105-.154-.298-.23l-5.384-2q-.096-.04-.212-.04t-.212.04l-5.384 2q-.193.076-.298.23Q6 6.606 6 6.798V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.861");
}

</style>

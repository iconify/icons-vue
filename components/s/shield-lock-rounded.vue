<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j218aachq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-lock-rounded" /></template>
<style>
.j218aachq {
  fill: currentColor;
  d: path("M10.039 15.654h3.923q.343 0 .575-.232t.232-.576v-2.923q0-.343-.232-.575t-.576-.232h-.173v-1q0-.749-.51-1.26q-.51-.51-1.259-.51t-1.259.51t-.51 1.26v1h-.212q-.343 0-.575.232t-.232.575v2.923q0 .344.232.576t.576.232m.98-4.538v-1q0-.425.288-.713t.712-.288t.713.288t.287.713v1zm.694 9.701q-.15-.025-.28-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.514.293-.926q.292-.412.757-.597l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.464.186.757.597q.293.412.293.926V11.1q0 3.135-1.74 5.826t-4.692 3.816q-.131.05-.281.075t-.287.025t-.287-.025");
}

</style>

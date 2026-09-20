<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9hiprbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:manage-search-outline-sharp" /></template>
<style>
.e9hiprbbx {
  fill: currentColor;
  d: path("M3 17.962v-1h9.558v1zm0-4.789v-1h4.462v1zm0-4.788v-1h4.462v1zM20.292 18l-3.888-3.83q-.543.405-1.178.627q-.636.222-1.303.222q-1.684 0-2.87-1.164q-1.188-1.164-1.188-2.845t1.188-2.845Q12.242 7 13.928 7t2.869 1.165T17.981 11q0 .667-.222 1.303q-.223.636-.648 1.159L21 17.292zm-6.369-3.98q1.274 0 2.166-.876q.892-.875.892-2.135t-.892-2.134T13.923 8t-2.166.875t-.892 2.135t.892 2.134t2.166.875");
}

</style>

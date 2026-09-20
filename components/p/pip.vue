<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eneviw4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pip" /></template>
<style>
.eneviw4ox {
  fill: currentColor;
  d: path("M3 10.616v-1h3.927l-5.55-5.531l.707-.708l5.532 5.53V5h1v5.616zM4.616 19q-.691 0-1.153-.462T3 17.384V13h1v4.385q0 .269.173.442t.443.173h7.153v1zM20 12.77V6.615q0-.27-.173-.443T19.385 6H11V5h8.385q.69 0 1.153.463T21 6.616v6.153zM14.154 19v-3.846H21V19z");
}

</style>

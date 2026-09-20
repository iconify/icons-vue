<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lil1zrbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opensuse-tumbleweed-alt" /></template>
<style>
.lil1zrbuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.296 29.304A7.5 7.5 0 1 1 7.69 18.697a7.5 7.5 0 0 1 10.607 0M29.704 28.95c2.929 2.734 7.678 2.734 10.607 0s2.929-7.165 0-9.899s-7.677-2.734-10.607 0M18.296 29.304L29.704 19.05m-9.908 3.648h2.5v-2.5m6.408 5.252h-2.5v2.5m-7.908-9.252l3.5 3.5m7.908 6.752l-3.5-3.5");
}

</style>

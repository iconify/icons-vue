<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl4jlbbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-power-drill-sharp" /></template>
<style>
.kl4jlbbib {
  fill: currentColor;
  d: path("M6 10h6V8.5H6zm0-2.5h6V6H6zM17 11V5h2l1 1v1h3v2h-3v1l-1 1zM6 15.5V13q-1.65 0-2.825-1.175T2 9V7q0-1.65 1.175-2.825T6 3h10v10h-4v2.5zM4 21v-4.5h10V21z");
}

</style>

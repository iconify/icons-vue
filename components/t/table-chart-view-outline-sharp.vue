<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojuj4ybys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-chart-view-outline-sharp" /></template>
<style>
.ojuj4ybys {
  fill: currentColor;
  d: path("m7.4 21.308l-.708-.708l6.208-6.213l3.5 3.5l5.175-5.175l.713.713l-5.888 5.883l-3.5-3.5zM4.615 20H3V4h16v6H4v9h.616zM4 9h14V5H4zm0 0V5z");
}

</style>

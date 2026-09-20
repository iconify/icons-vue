<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cev-g6t_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wall-art" /></template>
<style>
.cev-g6t_z {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V8.615q0-.69.463-1.152T4.615 7h4.27L12 3.885L15.116 7h4.269q.69 0 1.153.463T21 8.616v10.769q0 .69-.462 1.153T19.385 21zM7.5 17.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zm10.216-4.822q.323-.322.323-.793t-.323-.794t-.793-.322t-.793.322t-.322.793t.322.794t.793.322t.793-.322M10.138 7h3.724L12 5.139z");
}

</style>

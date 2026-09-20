<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/u7xoa2amh.css';
import '../../css/z/z7h9dmbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="u7xoa2amh"/><rect class="z7h9dmbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trash-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l6vmmtihn.css';
import '../../css/q/q3hr0d51s.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="l6vmmtihn"/><path class="q3hr0d51s"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:power-circle-off" /></template>

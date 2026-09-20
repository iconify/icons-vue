<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/un5eawvbo.css';
import '../../css/r/rd0ahsbfx.css';
import '../../css/c/cig-abbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="un5eawvbo"/><path class="rd0ahsbfx"/><path clip-rule="evenodd" class="cig-abbjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:nightstand-duotone" /></template>

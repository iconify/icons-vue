<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c-06v8b3s.css';
import '../../css/j/j1whpvfgt.css';
import '../../css/n/nisg9rpsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c-06v8b3s"/><path class="j1whpvfgt"/><path class="nisg9rpsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mortarboard-square2-duotone" /></template>

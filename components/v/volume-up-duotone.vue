<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iwqi-5bwl.css';
import '../../css/w/wz5f-bcbc.css';
import '../../css/y/yiu_zb82h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iwqi-5bwl"/><path clip-rule="evenodd" class="wz5f-bcbc"/><path clip-rule="evenodd" class="yiu_zb82h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-up-duotone" /></template>

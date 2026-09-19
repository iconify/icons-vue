<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/yskvirclu.css';
import '../../css/w/wnu5hjbyz.css';
import '../../css/j/j7-ykzbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yskvirclu"/><path class="wnu5hjbyz"/><path class="j7-ykzbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:scale-frame-reduce" /></template>

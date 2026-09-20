<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i0mshkbiy.css';
import '../../css/h/hbya5l-0v.css';
import '../../css/d/d7557zb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i0mshkbiy"/><path clip-rule="evenodd" class="hbya5l-0v"/><path class="d7557zb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-plus2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tg1onllgj.css';
import '../../css/j/j7hzqfbli.css';
import '../../css/z/zuqh_gv5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tg1onllgj"/><path class="j7hzqfbli"/><path clip-rule="evenodd" class="zuqh_gv5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:receive-square-outline" /></template>

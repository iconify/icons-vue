<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sei3qab8x.css';
import '../../css/f/f23ximbyn.css';
import '../../css/i/iy0e64bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="sei3qab8x"/><path clip-rule="evenodd" class="f23ximbyn"/><path class="iy0e64bfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:today" /></template>

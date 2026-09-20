<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zyr2z0cpz.css';
import '../../css/b/bhcv8nimm.css';
import '../../css/x/xxaranb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zyr2z0cpz"/><path class="bhcv8nimm"/><path clip-rule="evenodd" class="xxaranb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:router2" /></template>

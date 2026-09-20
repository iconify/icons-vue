<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ibo2hx6gt.css';
import '../../css/k/ko5sjbb8w.css';
import '../../css/l/l4llv2krk.css';
import '../../css/l/li71x2-ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ibo2hx6gt"/><path class="ko5sjbb8w"/><path class="l4llv2krk"/><path class="li71x2-ig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:open" /></template>

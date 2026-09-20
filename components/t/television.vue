<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iv2sj7z_t.css';
import '../../css/b/b6x92hbvb.css';
import '../../css/v/vk5wnopgr.css';
import '../../css/w/wzmvinbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iv2sj7z_t"/><path clip-rule="evenodd" class="b6x92hbvb"/><path class="vk5wnopgr"/><path class="wzmvinbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:television" /></template>

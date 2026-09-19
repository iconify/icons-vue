<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/kbumho25s.css';
import '../../css/x/xtd9eubfb.css';
import '../../css/r/r8g_vabug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="h01tyzbfu"><path class="kbumho25s"/><path class="xtd9eubfb"/><path class="r8g_vabug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-2" /></template>

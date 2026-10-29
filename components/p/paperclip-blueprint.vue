<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/pnw747ntt.css';
import '../../css/r/rz1izdbtt.css';
import '../../css/e/e8u9hlbvz.css';
import '../../css/v/vo6e5ybat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="pnw747ntt wm-deco"/><path class="rz1izdbtt wm-deco"/><path class="e8u9hlbvz"/><path class="vo6e5ybat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paperclip-blueprint" /></template>

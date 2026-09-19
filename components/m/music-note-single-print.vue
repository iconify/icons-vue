<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ra-b9gbrc.css';
import '../../css/x/xzibufbij.css';
import '../../css/g/g9vaapbcx.css';
import '../../css/s/s1ahl8q5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ra-b9gbrc"/><path clip-rule="evenodd" class="xzibufbij"/><path class="g9vaapbcx"/><path clip-rule="evenodd" class="s1ahl8q5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:music-note-single-print" /></template>

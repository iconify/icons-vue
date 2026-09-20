<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/imnimkbei.css';
import '../../css/e/ed-8o3t8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="imnimkbei"/><path class="ed-8o3t8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:play-outline" /></template>

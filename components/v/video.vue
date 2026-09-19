<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsdao61r.css';
import '../../css/z/zc3lmmbma.css';
import '../../css/v/vbv_9ysna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="zc3lmmbma"/><path class="vbv_9ysna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:video" /></template>

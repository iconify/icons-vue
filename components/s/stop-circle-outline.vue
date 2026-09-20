<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/u9mbdp5lw.css';
import '../../css/z/zt_l6p9nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="u9mbdp5lw"/><path class="zt_l6p9nm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stop-circle-outline" /></template>

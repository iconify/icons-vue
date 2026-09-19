<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wlavnba7b.css';
import '../../css/q/q6e25zbab.css';
import '../../css/r/rci3dcsby.css';
import '../../css/u/uwn3tbuio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><circle class="wlavnba7b"/><path class="q6e25zbab"/><circle class="rci3dcsby"/><path class="uwn3tbuio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:male-female" /></template>

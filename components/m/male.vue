<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/akzewbc_j.css';
import '../../css/t/t_oz4bcyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="cuyn6tgcc"><circle class="akzewbc_j"/><path class="t_oz4bcyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:male" /></template>

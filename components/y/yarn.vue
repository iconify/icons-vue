<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5hj_1brq.css';
import '../../css/d/d6up25bex.css';
import '../../css/z/ziil8acyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="p5hj_1brq"><path transform="matrix(.1608 0 0 .16076 -.053 -.054)" class="d6up25bex"/><path transform="matrix(.1608 0 0 .16076 -.053 -.054)" class="ziil8acyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:yarn" /></template>

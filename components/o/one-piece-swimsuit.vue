<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6vylkbxi.css';
import '../../css/g/g9spk5brk.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/z/zp-tryb2x.css';
import '../../css/h/h9f382bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c6vylkbxi"/><path class="g9spk5brk"/><g class="jn8qy4bru"><path class="zp-tryb2x"/><path class="h9f382bvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:one-piece-swimsuit" /></template>

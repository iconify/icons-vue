<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqrt1ty8j.css';
import '../../css/r/rsh-9wb7s.css';
import '../../css/v/vsecb4i9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="dqrt1ty8j"/><path class="rsh-9wb7s"/><path class="vsecb4i9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:music-note-beamed" /></template>

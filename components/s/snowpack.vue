<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clsdao61r.css';
import '../../css/l/l3ykglrhy.css';
import '../../css/c/c223jf_pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="l3ykglrhy"/><path class="c223jf_pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:snowpack" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jlijy7b6j.css';
import '../../css/p/pqys9m2th.css';
import '../../css/m/mfynv6ahr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="jlijy7b6j"/><path class="pqys9m2th"/><path clip-rule="evenodd" class="mfynv6ahr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:root-folder-opened" /></template>

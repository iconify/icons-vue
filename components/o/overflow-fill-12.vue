<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/njrtzgfnc.css';
import '../../css/s/slwp9yb5h.css';
import '../../css/k/klebjebfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><circle class="njrtzgfnc"/><circle class="slwp9yb5h"/><circle class="klebjebfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:overflow-fill-12" /></template>

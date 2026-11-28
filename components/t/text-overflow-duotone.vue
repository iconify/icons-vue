<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pq8m5ccti.css';
import '../../css/k/kl5l34bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pq8m5ccti"/><path class="kl5l34bnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-overflow-duotone" /></template>

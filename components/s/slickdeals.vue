<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r13vadc4w.css';
import '../../css/c/cxb1kbche.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r13vadc4w"/><path class="cxb1kbche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slickdeals" /></template>

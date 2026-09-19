<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5dpu-bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="r5dpu-bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square" /></template>

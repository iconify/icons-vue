<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcd1uub9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qcd1uub9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:square-star" /></template>

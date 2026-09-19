<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy0lwfb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="yy0lwfb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:toilet" /></template>

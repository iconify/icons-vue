<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exngh_byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="exngh_byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pennant" /></template>

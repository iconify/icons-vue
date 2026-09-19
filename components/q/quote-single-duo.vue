<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlv7vxu_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rlv7vxu_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:quote-single-duo" /></template>

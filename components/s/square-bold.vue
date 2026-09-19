<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk_1t8jzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<rect class="kk_1t8jzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-bold" /></template>

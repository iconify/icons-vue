<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw20lybgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bw20lybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:three-duo" /></template>

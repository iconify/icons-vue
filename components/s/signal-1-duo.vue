<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_x5j7b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o_x5j7b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-1-duo" /></template>

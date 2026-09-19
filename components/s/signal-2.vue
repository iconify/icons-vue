<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2bvri4qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w2bvri4qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-2" /></template>

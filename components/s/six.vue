<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2s38yz9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x2s38yz9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:six" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us361hl1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="us361hl1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tablet-bold" /></template>

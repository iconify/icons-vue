<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8y80gtls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x8y80gtls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:r" /></template>

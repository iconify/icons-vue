<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5_-s9p0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="e5_-s9p0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:strikethrough" /></template>

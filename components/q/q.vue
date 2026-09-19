<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6ezqygrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="e6ezqygrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:q" /></template>

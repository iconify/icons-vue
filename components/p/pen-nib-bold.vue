<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5cj3ywlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p5cj3ywlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pen-nib-bold" /></template>

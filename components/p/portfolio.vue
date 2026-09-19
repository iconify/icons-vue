<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj5mqpb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gj5mqpb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:portfolio" /></template>

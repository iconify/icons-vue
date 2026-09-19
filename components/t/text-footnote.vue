<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0v0s9b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0v0s9b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-footnote" /></template>

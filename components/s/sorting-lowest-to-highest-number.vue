<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruxfll-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ruxfll-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sorting-lowest-to-highest-number" /></template>

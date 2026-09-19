<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6e31r93c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6e31r93c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:update-complete" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs9xiaclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qs9xiaclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partly-cloudy-night" /></template>

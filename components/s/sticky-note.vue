<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzlmh9erd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzlmh9erd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sticky-note" /></template>

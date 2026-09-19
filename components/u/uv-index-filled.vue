<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is2eirfur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="is2eirfur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:uv-index-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-8kcn42z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t-8kcn42z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:underline-outline" /></template>

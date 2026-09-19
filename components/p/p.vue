<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n38uvsbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="n38uvsbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:p" /></template>

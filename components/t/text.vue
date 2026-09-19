<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5k4lwueq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u5k4lwueq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:text" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jut4up8jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jut4up8jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkle-bold" /></template>

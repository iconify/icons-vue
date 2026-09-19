<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t519h8eza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t519h8eza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkle" /></template>

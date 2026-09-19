<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kggs5hblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kggs5hblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:o-duo" /></template>

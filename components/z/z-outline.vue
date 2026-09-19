<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkyxxnwcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jkyxxnwcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:z-outline" /></template>

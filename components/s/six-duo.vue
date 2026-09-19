<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkrb35bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jkrb35bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:six-duo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdfo5r-_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qdfo5r-_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:wolfram-wordmark" /></template>

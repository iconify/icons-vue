<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/josv8_q2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="josv8_q2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:one" /></template>

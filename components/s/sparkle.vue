<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o130g5b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o130g5b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sparkle" /></template>

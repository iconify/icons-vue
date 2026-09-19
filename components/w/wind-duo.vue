<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krwqt2j0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="krwqt2j0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wind-duo" /></template>

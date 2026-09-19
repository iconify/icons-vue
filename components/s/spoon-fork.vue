<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyph80boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eyph80boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:spoon-fork" /></template>

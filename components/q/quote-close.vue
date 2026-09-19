<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlo6nbbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rlo6nbbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:quote-close" /></template>

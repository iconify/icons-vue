<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbta3-b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hbta3-b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:two-arrow-in-left-right" /></template>

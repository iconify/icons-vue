<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt297qria.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="dt297qria"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sheep" /></template>

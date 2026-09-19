<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1gttdbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="i1gttdbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:seriff" /></template>

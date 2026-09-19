<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4tehhumr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="u4tehhumr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:tag-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0o8jbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="lt0o8jbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:map-3" /></template>

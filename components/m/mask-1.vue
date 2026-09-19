<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzrd1icfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="kzrd1icfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mask-1" /></template>

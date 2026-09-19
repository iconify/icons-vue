<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4uk9ab4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="h4uk9ab4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:signal-3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev2x8s2oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="ev2x8s2oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:umbrella-sea" /></template>

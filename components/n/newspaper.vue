<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch7d5hy0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ch7d5hy0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:newspaper" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1yekgbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="j1yekgbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:male" /></template>

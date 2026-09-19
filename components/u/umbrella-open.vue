<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9y7tdhpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="i9y7tdhpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:umbrella-open" /></template>

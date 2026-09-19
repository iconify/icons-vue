<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofg7ycc6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ofg7ycc6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ribbon" /></template>

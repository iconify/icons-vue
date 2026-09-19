<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_fl3cb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="d_fl3cb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:note-2" /></template>

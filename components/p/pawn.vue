<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdp7c3a2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="fdp7c3a2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:pawn" /></template>

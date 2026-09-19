<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqigswr5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pqigswr5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:star-cross" /></template>

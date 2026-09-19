<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt5cytbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="pt5cytbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:music-note" /></template>

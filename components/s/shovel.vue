<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyawn68za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="wyawn68za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:shovel" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyr8vnyio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="vyr8vnyio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:sign-road-1" /></template>

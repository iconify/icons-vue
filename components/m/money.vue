<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igz9ekoxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="igz9ekoxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:money" /></template>

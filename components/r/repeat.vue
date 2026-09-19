<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5a9aobrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="c5a9aobrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:repeat" /></template>

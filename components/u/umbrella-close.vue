<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9107n9gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="f9107n9gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:umbrella-close" /></template>

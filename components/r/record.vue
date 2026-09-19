<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1-ankmjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="h1-ankmjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:record" /></template>

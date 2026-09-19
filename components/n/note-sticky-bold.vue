<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e57oocc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e57oocc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-sticky-bold" /></template>

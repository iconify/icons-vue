<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd_xlpb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fd_xlpb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:peace-outline" /></template>

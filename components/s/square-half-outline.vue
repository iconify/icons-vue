<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpkcm5but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mpkcm5but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half-outline" /></template>

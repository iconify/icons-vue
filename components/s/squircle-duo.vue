<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmku7mbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wmku7mbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:squircle-duo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8vbjr1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vq8vbjr1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pin-outline" /></template>

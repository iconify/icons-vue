<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f39atyb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f39atyb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ruler-trinangle-bold" /></template>

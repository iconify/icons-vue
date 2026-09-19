<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0xyldb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v0xyldb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-half-1-outline" /></template>

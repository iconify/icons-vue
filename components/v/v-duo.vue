<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0ovf5b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p0ovf5b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:v-duo" /></template>

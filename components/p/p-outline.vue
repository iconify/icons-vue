<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt89g0bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nt89g0bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:p-outline" /></template>

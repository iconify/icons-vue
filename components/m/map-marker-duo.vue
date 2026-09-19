<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe0-zvsab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pe0-zvsab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map-marker-duo" /></template>

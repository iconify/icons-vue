<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwfoiyz9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nwfoiyz9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map-marker-line-bold" /></template>

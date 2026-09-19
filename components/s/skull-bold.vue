<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-cbvub-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l-cbvub-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:skull-bold" /></template>

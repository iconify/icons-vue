<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utulh6bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="utulh6bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:s-outline" /></template>

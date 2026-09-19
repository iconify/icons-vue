<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz2twmlmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nz2twmlmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-5-duo" /></template>

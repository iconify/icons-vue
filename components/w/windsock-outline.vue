<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6k8eclde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r6k8eclde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:windsock-outline" /></template>

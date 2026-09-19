<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezp74yeys.css';
import '../../css/a/a__s2g6zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<defs><path id="SVGcKbddeti" class="ezp74yeys"/></defs><g class="a__s2g6zp"><use href="#SVGcKbddeti"/><use href="#SVGcKbddeti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tilde-bold" /></template>

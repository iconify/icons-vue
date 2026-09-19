<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csa0z4bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="csa0z4bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:picnic-table" /></template>

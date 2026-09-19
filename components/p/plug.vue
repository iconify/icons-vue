<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cptk9ebxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cptk9ebxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plug" /></template>

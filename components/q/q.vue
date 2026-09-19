<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce-4x0bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ce-4x0bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:q" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebzc7_bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ebzc7_bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunrise-1" /></template>

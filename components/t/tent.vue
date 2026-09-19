<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrl37cc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vrl37cc2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tent" /></template>

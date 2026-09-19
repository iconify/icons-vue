<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji7iwovju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ji7iwovju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spinner" /></template>

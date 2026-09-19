<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xizt2jvwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xizt2jvwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:zero" /></template>

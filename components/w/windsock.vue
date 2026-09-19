<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3d0i0bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="z3d0i0bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:windsock" /></template>

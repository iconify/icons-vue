<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg29-bb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vg29-bb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:waves-1-bold" /></template>

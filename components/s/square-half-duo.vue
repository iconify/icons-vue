<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3r2cj34a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="o3r2cj34a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half-duo" /></template>

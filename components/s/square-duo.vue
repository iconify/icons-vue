<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vib408mob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vib408mob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-duo" /></template>

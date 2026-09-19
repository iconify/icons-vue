<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uju-xcg-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uju-xcg-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:play-duo" /></template>

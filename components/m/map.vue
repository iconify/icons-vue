<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5ph0tfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ng5ph0tfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map" /></template>

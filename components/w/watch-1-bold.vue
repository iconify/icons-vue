<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivepwjbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ivepwjbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:watch-1-bold" /></template>

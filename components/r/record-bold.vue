<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyzm3zbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fyzm3zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:record-bold" /></template>

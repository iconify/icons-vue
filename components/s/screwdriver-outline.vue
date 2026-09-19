<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l80po2zqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l80po2zqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:screwdriver-outline" /></template>

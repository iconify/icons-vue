<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo2crbouy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yo2crbouy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:receipt-bold" /></template>

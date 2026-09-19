<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0hu2obfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m0hu2obfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ticket-1-bold" /></template>

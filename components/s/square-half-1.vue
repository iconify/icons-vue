<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6qrxbmmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v6qrxbmmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square-half-1" /></template>

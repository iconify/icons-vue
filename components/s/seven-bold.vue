<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az0bjmbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="az0bjmbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seven-bold" /></template>

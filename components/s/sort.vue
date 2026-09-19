<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzgayr8xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kzgayr8xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sort" /></template>

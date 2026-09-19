<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n20eu0b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n20eu0b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shoe-print-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp5lgw7sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sp5lgw7sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:meh-bold" /></template>

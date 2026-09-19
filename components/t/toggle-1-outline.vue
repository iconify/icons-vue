<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kppf60czi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kppf60czi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:toggle-1-outline" /></template>

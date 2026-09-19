<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms5-zbb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ms5-zbb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pennant-1-outline" /></template>

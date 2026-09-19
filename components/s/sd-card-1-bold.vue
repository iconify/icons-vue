<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_kk4nbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h_kk4nbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sd-card-1-bold" /></template>

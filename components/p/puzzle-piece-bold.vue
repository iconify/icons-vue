<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg1s3861r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":83,"height":82};
const content = `<path clip-rule="evenodd" class="rg1s3861r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:puzzle-piece-bold" /></template>

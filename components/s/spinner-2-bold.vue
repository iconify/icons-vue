<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgbds-orp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qgbds-orp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:spinner-2-bold" /></template>

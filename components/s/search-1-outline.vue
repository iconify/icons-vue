<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or3_f5cmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="or3_f5cmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:search-1-outline" /></template>

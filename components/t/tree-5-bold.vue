<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkr_rntfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkr_rntfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree-5-bold" /></template>

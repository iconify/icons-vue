<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6s-tdxlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n6s-tdxlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:o-outline" /></template>

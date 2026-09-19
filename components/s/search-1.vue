<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmkmgc1ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zmkmgc1ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:search-1" /></template>

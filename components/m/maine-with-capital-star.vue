<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pimcu1bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pimcu1bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:maine-with-capital-star" /></template>

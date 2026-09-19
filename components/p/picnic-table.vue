<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r54r9ib-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="r54r9ib-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:picnic-table" /></template>

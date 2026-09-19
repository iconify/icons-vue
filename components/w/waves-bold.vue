<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui32i6m3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ui32i6m3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:waves-bold" /></template>

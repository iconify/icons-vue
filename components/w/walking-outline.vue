<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqgck3bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hqgck3bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:walking-outline" /></template>

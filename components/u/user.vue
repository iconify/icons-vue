<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s38--pbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s38--pbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:user" /></template>

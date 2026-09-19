<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s66mxdb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s66mxdb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:waves-1-duo" /></template>

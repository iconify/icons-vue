<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5xnlbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wq5xnlbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trash-1" /></template>

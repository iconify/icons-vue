<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dziw1abwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dziw1abwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shovel-snow" /></template>

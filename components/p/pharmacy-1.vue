<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzprqip-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vzprqip-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pharmacy-1" /></template>

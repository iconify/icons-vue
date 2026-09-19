<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqgqhc_5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qqgqhc_5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunny-mostly-bold" /></template>

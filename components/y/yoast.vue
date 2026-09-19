<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc3mhcb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="dc3mhcb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:yoast" /></template>

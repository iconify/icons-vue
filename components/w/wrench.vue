<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s__lwjb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s__lwjb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wrench" /></template>

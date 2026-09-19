<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1vqtqi0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s1vqtqi0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:z" /></template>

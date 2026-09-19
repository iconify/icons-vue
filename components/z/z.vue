<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g06g2je2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g06g2je2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:z" /></template>

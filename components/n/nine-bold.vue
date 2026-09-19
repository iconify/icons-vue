<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9ikixbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g9ikixbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:nine-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iulq5fb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="iulq5fb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-pointer" /></template>

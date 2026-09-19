<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e87y_-jlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e87y_-jlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:street-light-2-outline" /></template>

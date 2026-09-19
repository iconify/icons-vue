<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1v8i60eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l1v8i60eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pin-1" /></template>

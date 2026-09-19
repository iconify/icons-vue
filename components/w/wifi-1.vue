<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-o8jnbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g-o8jnbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wifi-1" /></template>

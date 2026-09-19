<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/das0gdcyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="das0gdcyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:stumbleupon" /></template>

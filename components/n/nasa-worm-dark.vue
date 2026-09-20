<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djbz6iboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djbz6iboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-worm-dark" /></template>

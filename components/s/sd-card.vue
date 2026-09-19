<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcfw6kb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fcfw6kb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sd-card" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6ad0f7ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h6ad0f7ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkle-outline" /></template>

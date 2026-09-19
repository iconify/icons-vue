<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sawu3rbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sawu3rbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-outline" /></template>

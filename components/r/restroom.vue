<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo9elgb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vo9elgb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:restroom" /></template>

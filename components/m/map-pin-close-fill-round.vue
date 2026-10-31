<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0bv-nbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bv-nbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-close-fill-round" /></template>

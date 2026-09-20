<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fid1iybje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fid1iybje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scroll-to-bottom-line" /></template>

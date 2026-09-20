<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wloo1rwde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wloo1rwde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:tailwind-css-line" /></template>

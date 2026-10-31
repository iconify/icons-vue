<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch96rgbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch96rgbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-small-duotone-round" /></template>

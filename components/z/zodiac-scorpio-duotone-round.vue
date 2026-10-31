<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1pt29g_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pt29g_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-scorpio-duotone-round" /></template>

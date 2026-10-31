<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwr2qro4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwr2qro4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-taurus-fill-round" /></template>

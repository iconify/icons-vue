<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvngxob_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvngxob_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-scorpio" /></template>

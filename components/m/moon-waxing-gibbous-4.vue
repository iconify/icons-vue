<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsa_t_p5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="nsa_t_p5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-gibbous-4" /></template>

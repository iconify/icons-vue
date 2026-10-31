<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki311fb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki311fb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-round" /></template>

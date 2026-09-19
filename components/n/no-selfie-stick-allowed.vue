<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wul82ibrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wul82ibrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-selfie-stick-allowed" /></template>

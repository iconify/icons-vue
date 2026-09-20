<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm628pxnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm628pxnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:suitcase-2-line" /></template>

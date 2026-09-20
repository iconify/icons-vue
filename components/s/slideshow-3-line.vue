<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgh_qzbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh_qzbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-3-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swx55lw8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swx55lw8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-full-light" /></template>

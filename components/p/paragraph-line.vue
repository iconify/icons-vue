<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sahc2k4su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sahc2k4su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:paragraph-line" /></template>

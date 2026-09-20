<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tugg-6crg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tugg-6crg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speaker-fill" /></template>

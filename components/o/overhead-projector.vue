<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbcu94bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbcu94bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:overhead-projector" /></template>

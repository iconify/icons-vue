<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxeu6zgvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxeu6zgvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-remove-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwa6k3roj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwa6k3roj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-stream-outline" /></template>

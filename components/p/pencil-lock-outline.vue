<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee6bkskmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee6bkskmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-lock-outline" /></template>

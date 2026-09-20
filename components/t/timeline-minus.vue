<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sac4nqrrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sac4nqrrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-minus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrk2ge1sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrk2ge1sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-search" /></template>

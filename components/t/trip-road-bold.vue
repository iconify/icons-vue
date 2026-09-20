<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o11scyb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o11scyb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:trip-road-bold" /></template>

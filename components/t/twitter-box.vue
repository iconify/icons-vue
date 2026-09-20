<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_tbx5-0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_tbx5-0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:twitter-box" /></template>

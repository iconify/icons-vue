<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrl4igb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrl4igb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pound-box-outline" /></template>

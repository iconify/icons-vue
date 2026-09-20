<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9h931b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9h931b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-vertical" /></template>

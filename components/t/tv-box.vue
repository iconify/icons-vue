<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve6n4db7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6n4db7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tv-box" /></template>

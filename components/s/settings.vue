<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vshc7ebho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vshc7ebho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccrrbfbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccrrbfbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tray-arrow-down" /></template>

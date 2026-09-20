<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4ua6lb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4ua6lb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-azure" /></template>

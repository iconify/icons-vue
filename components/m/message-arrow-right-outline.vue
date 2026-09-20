<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0vmalbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0vmalbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-arrow-right-outline" /></template>

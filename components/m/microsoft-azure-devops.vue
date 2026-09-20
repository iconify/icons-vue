<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dib2neggl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dib2neggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-azure-devops" /></template>

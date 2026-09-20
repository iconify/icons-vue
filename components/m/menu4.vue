<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-gtm-bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-gtm-bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu4" /></template>

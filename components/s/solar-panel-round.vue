<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrd2btws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmrd2btws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:solar-panel-round" /></template>

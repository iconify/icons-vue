<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz70q30vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz70q30vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:steps-down-filled" /></template>

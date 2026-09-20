<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrb26zbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrb26zbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-electric" /></template>

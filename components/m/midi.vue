<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrjw5pb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjw5pb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:midi" /></template>

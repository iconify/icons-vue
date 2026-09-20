<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv_z1rwws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_z1rwws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-check-outline" /></template>

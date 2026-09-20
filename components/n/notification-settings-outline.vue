<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dss09dbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dss09dbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notification-settings-outline" /></template>

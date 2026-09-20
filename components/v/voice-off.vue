<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbkvt_4lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbkvt_4lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:voice-off" /></template>

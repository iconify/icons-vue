<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inx228uts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inx228uts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:webrtc" /></template>

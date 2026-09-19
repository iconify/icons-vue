<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vggrv1tof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vggrv1tof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-kids-bedroom" /></template>

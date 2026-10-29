<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr29w0dkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr29w0dkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:switch-camera-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrumi43vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrumi43vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-2-alert" /></template>

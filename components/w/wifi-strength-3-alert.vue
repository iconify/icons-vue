<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxr0uizak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxr0uizak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-3-alert" /></template>

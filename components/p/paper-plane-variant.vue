<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywt1lbbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywt1lbbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paper-plane-variant" /></template>

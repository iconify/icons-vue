<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy5grrbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zy5grrbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-vibration-outline" /></template>

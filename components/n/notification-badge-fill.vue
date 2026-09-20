<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mktnqtb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mktnqtb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-badge-fill" /></template>

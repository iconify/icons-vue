<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzi2x3e-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzi2x3e-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-user" /></template>

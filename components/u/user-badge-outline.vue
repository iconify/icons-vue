<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc3uy0b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3uy0b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-badge-outline" /></template>

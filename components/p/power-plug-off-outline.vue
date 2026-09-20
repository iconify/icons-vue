<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ick56cv-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ick56cv-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-plug-off-outline" /></template>

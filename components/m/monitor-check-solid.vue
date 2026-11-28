<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbt2vcxfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbt2vcxfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:monitor-check-solid" /></template>

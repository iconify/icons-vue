<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1q28xfug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q28xfug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:propane-tank-outline" /></template>

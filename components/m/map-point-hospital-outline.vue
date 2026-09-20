<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onb0tacme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="onb0tacme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-hospital-outline" /></template>

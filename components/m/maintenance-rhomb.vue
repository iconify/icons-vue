<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtpl83ikm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtpl83ikm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-rhomb" /></template>

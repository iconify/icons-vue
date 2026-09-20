<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-5v3uhca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-5v3uhca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sign-direction" /></template>

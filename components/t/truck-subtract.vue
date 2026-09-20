<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kug2_lg1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kug2_lg1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-subtract" /></template>

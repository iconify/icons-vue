<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8wg46bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8wg46bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:underwear-outline" /></template>

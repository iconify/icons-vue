<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaxtr4zwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaxtr4zwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:set-right" /></template>

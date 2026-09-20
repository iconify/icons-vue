<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dijeofbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dijeofbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-dashboard-edit" /></template>

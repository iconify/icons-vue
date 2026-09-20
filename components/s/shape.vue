<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg1d0enhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg1d0enhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape" /></template>

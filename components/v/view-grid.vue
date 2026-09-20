<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_7w4pyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_7w4pyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-grid" /></template>

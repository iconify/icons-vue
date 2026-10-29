<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6081t11q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6081t11q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pin-check" /></template>

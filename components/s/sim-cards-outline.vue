<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy6jbd7kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vy6jbd7kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-cards-outline" /></template>

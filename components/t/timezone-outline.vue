<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp1w73bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1w73bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timezone-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ub34b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ub34b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-minus-inside" /></template>

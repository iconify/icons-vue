<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ftcgbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7ftcgbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:notification-x" /></template>

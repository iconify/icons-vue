<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlweaw6kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wlweaw6kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlink-48" /></template>

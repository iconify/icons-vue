<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flw9b1kuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flw9b1kuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoke-detector-off" /></template>

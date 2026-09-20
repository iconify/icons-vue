<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-pmo43tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-pmo43tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:thermometer-sun" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihvpr_l5t.css';
import '../../css/e/e_x4yrbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihvpr_l5t"/><path class="e_x4yrbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-48-bold" /></template>

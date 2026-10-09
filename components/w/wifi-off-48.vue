<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzac5pbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rzac5pbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-off-48" /></template>

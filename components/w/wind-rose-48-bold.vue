<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn158vbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gn158vbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-rose-48-bold" /></template>

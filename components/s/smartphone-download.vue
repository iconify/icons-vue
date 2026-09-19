<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz6l9nihz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":480};
const content = `<path class="tz6l9nihz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-download" /></template>

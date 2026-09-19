<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc9hztbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="hc9hztbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tv-alt-play" /></template>

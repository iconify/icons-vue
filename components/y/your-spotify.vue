<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhut6ubwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhut6ubwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:your-spotify" /></template>

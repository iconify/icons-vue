<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1kf68bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1kf68bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solidtime-light" /></template>

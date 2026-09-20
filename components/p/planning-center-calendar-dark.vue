<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tszswib7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tszswib7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-calendar-dark" /></template>

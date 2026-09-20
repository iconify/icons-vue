<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv1qjubgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wv1qjubgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:timetagger-dark" /></template>

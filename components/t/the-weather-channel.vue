<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2rd5by9y.css';
import '../../css/k/kntrzcclo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2rd5by9y"/><path class="kntrzcclo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-weather-channel" /></template>

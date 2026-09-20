<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2zc8cbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j2zc8cbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-weather-channel-light" /></template>

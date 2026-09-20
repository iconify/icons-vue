<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix8txo7ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix8txo7ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netbird-dark" /></template>

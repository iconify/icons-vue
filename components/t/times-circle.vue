<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2jm7uoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hv2jm7uoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:times-circle" /></template>

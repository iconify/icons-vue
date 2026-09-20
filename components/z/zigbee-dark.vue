<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1u6t7xfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1u6t7xfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zigbee-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdo8u4pgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdo8u4pgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yourls-light" /></template>

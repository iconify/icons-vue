<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l48yp7bmv.css';
import '../../css/t/tmnz0vbmc.css';
import '../../css/r/r4qkfrbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l48yp7bmv"/><path class="tmnz0vbmc"/><path class="r4qkfrbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paypal-dark" /></template>

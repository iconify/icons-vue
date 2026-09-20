<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ko3vzuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x2ko3vzuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:philips-hue-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-eaap4bd.css';
import '../../css/f/f86310bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-eaap4bd"/><path class="f86310bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valetudo" /></template>

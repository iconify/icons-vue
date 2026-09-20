<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_98zbbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_98zbbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pico-dark" /></template>

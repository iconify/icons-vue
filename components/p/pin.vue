<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9znjbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vy9znjbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:pin" /></template>

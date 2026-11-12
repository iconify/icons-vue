<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqmp0xvom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqmp0xvom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamtx-light" /></template>

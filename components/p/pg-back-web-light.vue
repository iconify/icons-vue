<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdl17k87h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xdl17k87h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pg-back-web-light" /></template>

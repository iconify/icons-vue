<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcf0u5b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kcf0u5b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:socket-io-dark" /></template>

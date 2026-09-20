<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nulm-216m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nulm-216m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omniroute-dark" /></template>

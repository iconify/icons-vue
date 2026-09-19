<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsayvsvbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsayvsvbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:yin-yang" /></template>

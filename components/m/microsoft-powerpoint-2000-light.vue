<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptqwy9b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptqwy9b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-2000-light" /></template>

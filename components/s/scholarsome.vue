<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mttdjus_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mttdjus_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scholarsome" /></template>

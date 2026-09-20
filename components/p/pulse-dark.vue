<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1arryb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1arryb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulse-dark" /></template>

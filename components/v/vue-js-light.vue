<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqmq48xdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqmq48xdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vue-js-light" /></template>

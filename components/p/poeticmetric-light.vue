<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb-64f8xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tb-64f8xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:poeticmetric-light" /></template>

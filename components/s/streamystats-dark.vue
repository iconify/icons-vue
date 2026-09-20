<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms5fjbcnx.css';
import '../../css/c/c8oz1ac5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms5fjbcnx"/><path class="c8oz1ac5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamystats-dark" /></template>

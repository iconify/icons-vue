<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgbkh123w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgbkh123w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:recyclarr-dark" /></template>

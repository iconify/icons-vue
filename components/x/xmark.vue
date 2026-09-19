<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvaqsm1-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xvaqsm1-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:xmark" /></template>

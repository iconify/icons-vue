<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntr9l2cws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ntr9l2cws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tcp-ip-service" /></template>

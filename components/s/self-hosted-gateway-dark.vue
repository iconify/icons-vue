<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sghq9ybsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sghq9ybsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-gateway-dark" /></template>

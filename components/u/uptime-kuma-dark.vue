<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktgkes3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":622,"height":622};
const content = `<path class="ktgkes3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-kuma-dark" /></template>

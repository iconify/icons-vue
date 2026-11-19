<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgpp--bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgpp--bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:telltaledns-light" /></template>

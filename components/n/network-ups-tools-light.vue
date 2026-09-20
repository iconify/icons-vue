<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqbelnb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqbelnb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:network-ups-tools-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4ks7abcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4ks7abcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-manager-dark" /></template>

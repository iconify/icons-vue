<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exm-ov3sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="exm-ov3sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-light" /></template>

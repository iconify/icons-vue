<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chdjcu4lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="chdjcu4lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-manager-light" /></template>

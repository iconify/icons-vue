<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtjor1x3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dtjor1x3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portal-relay-dark" /></template>

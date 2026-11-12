<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxyj6fwnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxyj6fwnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omada" /></template>

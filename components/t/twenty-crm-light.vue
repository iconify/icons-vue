<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0amaqwhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0amaqwhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twenty-crm-light" /></template>

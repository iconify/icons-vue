<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0nmm2b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0nmm2b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openbooks-light" /></template>

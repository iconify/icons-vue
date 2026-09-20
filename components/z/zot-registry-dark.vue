<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtq_hhlkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtq_hhlkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zot-registry-dark" /></template>

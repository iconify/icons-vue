<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upmtxfbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="upmtxfbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nirvati-light" /></template>

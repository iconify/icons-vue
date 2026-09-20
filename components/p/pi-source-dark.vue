<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc4jvnbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pc4jvnbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-source-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbvf_vbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbvf_vbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prowlarr-dark" /></template>

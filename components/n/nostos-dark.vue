<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcqc_lbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gcqc_lbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nostos-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcdk4ubif.css';
import '../../css/b/baziz2k_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcdk4ubif"/><path class="baziz2k_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tracearr-dark" /></template>

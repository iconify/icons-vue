<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xus3r2plp.css';
import '../../css/u/u9q951uce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xus3r2plp"/><path class="u9q951uce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threadfin-light" /></template>

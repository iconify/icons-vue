<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk15ehbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kk15ehbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typo3-dark" /></template>

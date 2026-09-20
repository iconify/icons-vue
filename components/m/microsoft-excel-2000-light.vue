<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir7lnvtyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ir7lnvtyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2000-light" /></template>

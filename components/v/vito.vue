<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbm0u_bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbm0u_bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vito" /></template>

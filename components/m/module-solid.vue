<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stn_egbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="stn_egbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:module-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o44tc3byv.css';
import '../../css/e/eplvi-bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o44tc3byv"/><path class="eplvi-bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-velocity-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v95ogbcrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":408};
const content = `<path class="v95ogbcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mic" /></template>

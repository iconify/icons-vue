<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5wb8rbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5wb8rbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:revel-dark" /></template>

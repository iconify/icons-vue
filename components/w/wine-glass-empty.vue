<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0s0bu_wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="h0s0bu_wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wine-glass-empty" /></template>

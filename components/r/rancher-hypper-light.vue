<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38e-f2_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h38e-f2_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-hypper-light" /></template>

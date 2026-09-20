<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8_h0nxyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8_h0nxyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:namur-maintenance-required" /></template>

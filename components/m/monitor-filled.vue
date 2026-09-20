<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfb18lbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfb18lbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:monitor-filled" /></template>

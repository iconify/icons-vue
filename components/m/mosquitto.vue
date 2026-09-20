<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz0w159ze.css';
import '../../css/k/k5b4rgmdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz0w159ze"/><path class="k5b4rgmdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mosquitto" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xedtc1bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xedtc1bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-hypper-dark" /></template>

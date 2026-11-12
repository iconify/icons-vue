<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu0v_pbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mu0v_pbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-copilot-light" /></template>

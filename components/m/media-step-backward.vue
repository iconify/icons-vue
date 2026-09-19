<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl1m2nbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kl1m2nbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-step-backward" /></template>

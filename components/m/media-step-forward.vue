<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvtqc-bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rvtqc-bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-step-forward" /></template>

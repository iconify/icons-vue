<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkglbdcce.css';
import '../../css/t/ts0tfxa1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kkglbdcce"/><path class="ts0tfxa1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-at" /></template>

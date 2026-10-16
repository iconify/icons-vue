<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qht0pcczn.css';
import '../../css/m/mt2dtwjzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qht0pcczn"/><path class="mt2dtwjzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vr-headset-48-bold" /></template>

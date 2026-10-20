<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrurpboo.css';
import '../../css/v/vvmgcrxho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="vvmgcrxho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-sparkle-48" /></template>

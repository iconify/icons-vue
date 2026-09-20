<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tng3gzelg.css';
import '../../css/h/hzpmfc_wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tng3gzelg"/><path class="hzpmfc_wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-pin-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm5o86bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vm5o86bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:system" /></template>

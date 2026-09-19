<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwc-_dbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwc-_dbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:unplug" /></template>

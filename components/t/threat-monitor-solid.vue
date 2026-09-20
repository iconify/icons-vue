<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baljw1b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="baljw1b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:threat-monitor-solid" /></template>

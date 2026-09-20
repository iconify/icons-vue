<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9-2swyic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o9-2swyic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wave-signal-square-solid" /></template>

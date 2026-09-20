<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vug-92bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vug-92bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wrench-circle-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky31ddcxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ky31ddcxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:oceanengine" /></template>

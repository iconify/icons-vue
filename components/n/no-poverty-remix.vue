<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfis3eb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wfis3eb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:no-poverty-remix" /></template>

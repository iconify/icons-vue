<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfgz-i8ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cfgz-i8ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:payment-recieve-7-remix" /></template>

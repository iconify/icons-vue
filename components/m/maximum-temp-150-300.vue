<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrnnkbbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="xrnnkbbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:maximum-temp-150-300" /></template>

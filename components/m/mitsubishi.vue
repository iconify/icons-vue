<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebmm8_bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ebmm8_bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mitsubishi" /></template>

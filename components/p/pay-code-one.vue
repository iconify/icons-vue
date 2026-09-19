<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6au-ssag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e6au-ssag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pay-code-one" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwps6ee2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rwps6ee2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pay-code-two" /></template>

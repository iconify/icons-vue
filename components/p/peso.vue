<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f28z4wbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f28z4wbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:peso" /></template>

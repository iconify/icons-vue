<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxm9n-bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cxm9n-bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stopwatch-half-solid" /></template>

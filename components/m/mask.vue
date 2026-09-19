<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tah160b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tah160b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mask" /></template>

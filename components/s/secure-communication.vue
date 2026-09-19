<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omdwogh3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="omdwogh3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:secure-communication" /></template>

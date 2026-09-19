<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xddonpb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xddonpb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:z2x-outline" /></template>

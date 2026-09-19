<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzro4qbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xzro4qbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pain2x-outline" /></template>

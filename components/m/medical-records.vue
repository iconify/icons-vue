<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyelrf6uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xyelrf6uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-records" /></template>

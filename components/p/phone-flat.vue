<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hege8bcxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hege8bcxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:phone-flat" /></template>

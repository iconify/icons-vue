<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggkt217da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ggkt217da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:medical-files-report-history-remix" /></template>

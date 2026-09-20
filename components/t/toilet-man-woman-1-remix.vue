<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk8sppb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tk8sppb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:toilet-man-woman-1-remix" /></template>

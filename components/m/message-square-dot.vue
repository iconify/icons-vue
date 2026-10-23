<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt_gj5bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_gj5bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-dot" /></template>

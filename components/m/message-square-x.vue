<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up282vbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up282vbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-x" /></template>

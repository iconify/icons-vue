<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfoq_w78e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfoq_w78e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:unavailable-fill" /></template>

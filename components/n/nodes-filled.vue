<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uea_xyb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uea_xyb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:nodes-filled" /></template>

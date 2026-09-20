<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4m1t3bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4m1t3bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-box-multiple" /></template>

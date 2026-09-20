<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izdezhb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izdezhb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-zero-box-multiple-outline" /></template>

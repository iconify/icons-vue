<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc0ra4bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc0ra4bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roku" /></template>

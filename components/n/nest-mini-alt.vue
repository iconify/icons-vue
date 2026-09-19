<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en8znknyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en8znknyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nest-mini-alt" /></template>

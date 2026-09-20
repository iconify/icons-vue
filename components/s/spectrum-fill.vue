<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r12dccgbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r12dccgbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spectrum-fill" /></template>

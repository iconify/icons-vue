<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqq_kvcwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqq_kvcwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uegkk1bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uegkk1bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pass-pending-fill" /></template>

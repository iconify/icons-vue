<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwwb-nbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwwb-nbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stethoscope-outline-24px" /></template>

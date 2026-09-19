<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvsgdb6ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvsgdb6ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:prostate-24px" /></template>

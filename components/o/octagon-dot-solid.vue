<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsv8pkbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsv8pkbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:octagon-dot-solid" /></template>

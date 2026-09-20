<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6axq2bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6axq2bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-down-bold" /></template>

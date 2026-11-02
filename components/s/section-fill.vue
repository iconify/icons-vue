<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru30nfcqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru30nfcqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:section-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gukuj2bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gukuj2bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:report-tree" /></template>

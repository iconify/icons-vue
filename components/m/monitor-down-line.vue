<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isbsl39ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isbsl39ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-down-line" /></template>

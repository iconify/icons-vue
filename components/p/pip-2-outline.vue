<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh46y3bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qh46y3bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pip-2-outline" /></template>

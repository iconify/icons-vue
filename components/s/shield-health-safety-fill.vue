<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyyulzbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyyulzbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-health-safety-fill" /></template>

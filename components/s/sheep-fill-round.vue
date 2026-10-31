<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts5c0usmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts5c0usmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sheep-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrtt16bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtt16bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-one-solid" /></template>

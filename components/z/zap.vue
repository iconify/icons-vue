<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnvvvmbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnvvvmbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:zap" /></template>

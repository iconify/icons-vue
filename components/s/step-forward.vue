<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf-8gmbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-8gmbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:step-forward" /></template>

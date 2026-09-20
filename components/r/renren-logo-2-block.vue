<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wko_cm2kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wko_cm2kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:renren-logo-2-block" /></template>

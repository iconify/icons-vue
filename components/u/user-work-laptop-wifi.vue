<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgo_xyhzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgo_xyhzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-work-laptop-wifi" /></template>

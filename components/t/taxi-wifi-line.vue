<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy11gn_xc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy11gn_xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:taxi-wifi-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyw6vlvsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyw6vlvsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-ring" /></template>

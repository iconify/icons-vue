<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td3hcutdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td3hcutdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartphone-lock" /></template>

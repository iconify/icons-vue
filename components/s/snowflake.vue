<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onyt8rbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onyt8rbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:snowflake" /></template>

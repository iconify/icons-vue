<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqhh4obaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqhh4obaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thermometer-snowflake" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgnvp1com.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnvp1com"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paper-plane" /></template>

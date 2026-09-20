<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr1apkucb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr1apkucb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:nodejs-fill" /></template>

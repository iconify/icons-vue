<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6ppwziu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6ppwziu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wallet-line" /></template>

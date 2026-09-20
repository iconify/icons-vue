<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbyi8zb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbyi8zb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:voelkner" /></template>

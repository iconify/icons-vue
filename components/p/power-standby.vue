<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omd7uhbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="omd7uhbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:power-standby" /></template>

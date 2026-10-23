<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myb11n1qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myb11n1qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pi" /></template>

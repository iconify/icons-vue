<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hws676qlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hws676qlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-check-line" /></template>

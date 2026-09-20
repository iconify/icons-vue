<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a012c5bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a012c5bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:send" /></template>

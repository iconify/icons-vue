<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjal19bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjal19bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-pen" /></template>

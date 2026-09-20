<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yllo6ib3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yllo6ib3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-square-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuj9c8f4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuj9c8f4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stack-overflow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3xk5bt5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3xk5bt5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:shield-off" /></template>

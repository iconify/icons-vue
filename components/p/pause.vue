<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaj6s54mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaj6s54mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pause" /></template>

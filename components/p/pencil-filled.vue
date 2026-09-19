<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3t46bctj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3t46bctj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-filled" /></template>

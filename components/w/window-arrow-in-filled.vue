<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqjs2qjlu.css';
import '../../css/l/lsmjwzymg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqjs2qjlu"/><path class="lsmjwzymg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:window-arrow-in-filled" /></template>

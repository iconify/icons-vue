<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoe6q-b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoe6q-b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:slice" /></template>

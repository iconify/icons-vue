<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nth2ntb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nth2ntb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scan-ar-filled" /></template>

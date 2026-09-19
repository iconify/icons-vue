<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_pe8dxch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_pe8dxch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spray-can-filled" /></template>

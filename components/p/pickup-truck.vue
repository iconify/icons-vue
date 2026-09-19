<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef24_sbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef24_sbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pickup-truck" /></template>

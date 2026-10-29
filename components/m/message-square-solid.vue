<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sir6kksaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sir6kksaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-solid" /></template>

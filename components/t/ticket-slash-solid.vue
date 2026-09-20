<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i07x-u5sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i07x-u5sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ticket-slash-solid" /></template>

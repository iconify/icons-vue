<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru3g04bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3g04bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-square" /></template>

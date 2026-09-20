<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_57g8b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_57g8b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:six-solid" /></template>

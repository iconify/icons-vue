<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v51z1pfeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v51z1pfeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stop" /></template>

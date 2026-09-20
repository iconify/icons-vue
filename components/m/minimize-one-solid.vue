<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtbv83b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtbv83b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minimize-one-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npfc-cbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npfc-cbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sms-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqi7m4bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqi7m4bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:maximize-one" /></template>

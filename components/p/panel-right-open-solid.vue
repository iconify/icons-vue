<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roucozblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roucozblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-right-open-solid" /></template>

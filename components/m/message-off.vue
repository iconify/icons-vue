<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mywlo63po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mywlo63po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-off" /></template>

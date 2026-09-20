<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8bi2496u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8bi2496u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-left-inactive" /></template>

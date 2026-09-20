<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neqmi2sea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neqmi2sea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pen" /></template>

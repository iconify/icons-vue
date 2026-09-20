<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7lg59b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7lg59b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-plus-solid" /></template>

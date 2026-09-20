<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb0box43i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb0box43i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-snooze-solid" /></template>

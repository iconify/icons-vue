<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2qxzdsyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2qxzdsyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sparkles-solid" /></template>

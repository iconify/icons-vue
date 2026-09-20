<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifj4yiyii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifj4yiyii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:umbrella-off-solid" /></template>

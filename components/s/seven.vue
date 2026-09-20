<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wux24jb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wux24jb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:seven" /></template>

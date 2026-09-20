<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxuasu26p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxuasu26p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen" /></template>

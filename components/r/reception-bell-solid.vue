<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/filr94yjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="filr94yjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:reception-bell-solid" /></template>

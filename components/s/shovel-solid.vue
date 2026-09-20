<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn5kq1bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn5kq1bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shovel-solid" /></template>

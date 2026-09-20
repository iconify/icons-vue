<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzx2cnbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzx2cnbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:nine" /></template>

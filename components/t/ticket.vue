<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee2htrkye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee2htrkye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ticket" /></template>

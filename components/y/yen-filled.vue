<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gatosv7be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gatosv7be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:yen-filled" /></template>

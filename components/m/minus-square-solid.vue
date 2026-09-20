<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyvg-6-bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvg-6-bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-square-solid" /></template>

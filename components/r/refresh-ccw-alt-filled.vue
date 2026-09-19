<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxh9hzbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxh9hzbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:refresh-ccw-alt-filled" /></template>

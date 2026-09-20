<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiaeq12ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiaeq12ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:parking-fill" /></template>

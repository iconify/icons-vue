<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu3xoxbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu3xoxbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tower-4-fill" /></template>

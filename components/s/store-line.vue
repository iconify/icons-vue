<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo__o3b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo__o3b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-line" /></template>

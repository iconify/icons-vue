<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbunz6bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbunz6bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:medal-fill" /></template>

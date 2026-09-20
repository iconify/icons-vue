<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxc7bsk8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxc7bsk8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:users" /></template>

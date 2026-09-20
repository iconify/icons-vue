<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq4li-2nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq4li-2nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-plus" /></template>

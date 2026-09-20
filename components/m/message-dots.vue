<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3l7-nubk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3l7-nubk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-dots" /></template>

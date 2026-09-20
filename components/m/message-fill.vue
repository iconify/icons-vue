<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydwz119uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwz119uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:message-fill" /></template>

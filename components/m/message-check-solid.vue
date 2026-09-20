<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx0ez053t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx0ez053t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-check-solid" /></template>

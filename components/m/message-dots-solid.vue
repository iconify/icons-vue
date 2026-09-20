<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwzo7wbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwzo7wbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-dots-solid" /></template>

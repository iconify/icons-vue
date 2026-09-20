<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l83-ndbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l83-ndbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-arrow-left-outline" /></template>

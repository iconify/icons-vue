<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st2ssyqcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st2ssyqcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-text" /></template>

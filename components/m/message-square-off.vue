<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykb8jd99p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykb8jd99p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_2v_9b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p_2v_9b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:message" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm39wsvkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm39wsvkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:question-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ny4kbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1ny4kbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-plus" /></template>

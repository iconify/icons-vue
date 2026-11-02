<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq_2q37am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq_2q37am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-align-center-fill" /></template>

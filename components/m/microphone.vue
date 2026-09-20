<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_67od41a.css';
import '../../css/j/jhuhxq2cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q_67od41a"/><path class="jhuhxq2cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:microphone" /></template>

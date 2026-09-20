<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sat40obmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sat40obmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:voice-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so1iq5aai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so1iq5aai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sparkles" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht5rgbc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht5rgbc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ping-pong-fill" /></template>

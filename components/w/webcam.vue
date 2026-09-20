<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx7pczt_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx7pczt_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:webcam" /></template>

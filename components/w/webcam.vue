<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6k1nsv7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6k1nsv7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:webcam" /></template>

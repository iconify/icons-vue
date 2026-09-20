<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t75_zubnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t75_zubnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:mike2-outlined" /></template>

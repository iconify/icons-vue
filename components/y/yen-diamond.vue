<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhyuchb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhyuchb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-diamond" /></template>

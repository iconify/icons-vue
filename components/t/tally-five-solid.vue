<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7mhy5b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7mhy5b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-five-solid" /></template>

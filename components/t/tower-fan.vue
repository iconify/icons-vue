<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w66fu9bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w66fu9bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tower-fan" /></template>

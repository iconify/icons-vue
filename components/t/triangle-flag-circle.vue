<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsqgj0_wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsqgj0_wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:triangle-flag-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzw4rrtho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzw4rrtho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:riseup" /></template>

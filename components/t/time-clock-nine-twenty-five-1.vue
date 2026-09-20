<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6tui-2gp.css';
import '../../css/w/wyvbzqpgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6tui-2gp"/><path class="wyvbzqpgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:time-clock-nine-twenty-five-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhm5lux_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yhm5lux_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:receipt-subtract-remix" /></template>

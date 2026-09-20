<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv_a1b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rcv_a1b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:stock-remix" /></template>

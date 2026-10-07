<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcd003kth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcd003kth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swimming" /></template>

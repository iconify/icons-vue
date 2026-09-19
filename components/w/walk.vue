<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isr_9phgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1664};
const content = `<path class="isr_9phgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:walk" /></template>

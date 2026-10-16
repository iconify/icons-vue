<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsmnqk5do.css';
import '../../css/h/hqec9ivlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsmnqk5do"/><path class="hqec9ivlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-tester-20-bold" /></template>

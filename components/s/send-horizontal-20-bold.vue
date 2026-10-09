<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akipzwbge.css';
import '../../css/e/eimh7-87y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="akipzwbge"/><path class="eimh7-87y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-horizontal-20-bold" /></template>

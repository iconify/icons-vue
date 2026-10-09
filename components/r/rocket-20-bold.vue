<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv46repqa.css';
import '../../css/r/ra5u6pzcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kv46repqa"/><path class="ra5u6pzcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rocket-20-bold" /></template>

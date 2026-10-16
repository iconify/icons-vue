<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5fem0brp.css';
import '../../css/m/mu5t7mbov.css';
import '../../css/x/xyen0l77b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k5fem0brp"/><path class="mu5t7mbov"/><path class="xyen0l77b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-off-20-bold" /></template>

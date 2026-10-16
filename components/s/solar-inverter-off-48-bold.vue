<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-e1u6q-v.css';
import '../../css/y/ysk6l2evj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-e1u6q-v"/><path class="ysk6l2evj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-off-48-bold" /></template>

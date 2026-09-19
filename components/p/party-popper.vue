<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv8sgnbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zv8sgnbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:party-popper" /></template>

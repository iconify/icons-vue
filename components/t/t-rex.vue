<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylpsw_5zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ylpsw_5zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:t-rex" /></template>

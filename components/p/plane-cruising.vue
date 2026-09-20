<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oapu8s0xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oapu8s0xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-cruising" /></template>

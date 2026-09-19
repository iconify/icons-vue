<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1_to411n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q1_to411n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-dollar-circle" /></template>

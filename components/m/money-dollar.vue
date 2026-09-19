<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs_25ysim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gs_25ysim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-dollar" /></template>

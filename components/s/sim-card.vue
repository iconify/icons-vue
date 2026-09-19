<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpeu335fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hpeu335fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sim-card" /></template>

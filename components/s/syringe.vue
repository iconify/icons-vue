<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbkdobhmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zbkdobhmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:syringe" /></template>

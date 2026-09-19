<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu2bs-teb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="zu2bs-teb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mask-ventilator" /></template>

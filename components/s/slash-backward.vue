<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq-kp1o7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="eq-kp1o7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:slash-backward" /></template>

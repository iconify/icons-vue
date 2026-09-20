<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_0mqczo.css';
import '../../css/h/h7o1n1z4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f6_0mqczo"/><path class="h7o1n1z4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:speech-bubble-add-ltr" /></template>

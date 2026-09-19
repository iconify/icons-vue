<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v23ra87cd.css';
import '../../css/g/g8g7_q-fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v23ra87cd"/><path class="g8g7_q-fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:room" /></template>

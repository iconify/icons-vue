<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0dvj9g4i.css';
import '../../css/i/i2a3t5bgb.css';
import '../../css/t/tg1ou3w9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0dvj9g4i"/><path class="i2a3t5bgb"/><path class="tg1ou3w9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:socket-48" /></template>

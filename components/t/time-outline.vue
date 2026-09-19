<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-tflgzje.css';
import '../../css/i/ik34--bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="ik34--bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:time-outline" /></template>

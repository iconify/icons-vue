<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1xd6acdc.css';
import '../../css/q/q_650fa-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t1xd6acdc"/><path class="q_650fa-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-camera-20-bold" /></template>

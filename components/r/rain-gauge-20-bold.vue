<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ala7sfbdm.css';
import '../../css/t/tl7j9h2ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ala7sfbdm"/><path class="tl7j9h2ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rain-gauge-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/e/etrl1rckl.css';
import '../../css/x/x8kd897hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="etrl1rckl"/><path class="x8kd897hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tyre-20-bold" /></template>

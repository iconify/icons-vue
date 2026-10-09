<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfgle7bjr.css';
import '../../css/v/v8-70c-7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wfgle7bjr"/><path class="v8-70c-7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-axis-turbine-20" /></template>

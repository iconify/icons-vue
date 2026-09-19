<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf8ygpznr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wf8ygpznr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-font-awesome-stroke" /></template>

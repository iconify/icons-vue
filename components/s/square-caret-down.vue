<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlc0kwb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xlc0kwb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-caret-down" /></template>

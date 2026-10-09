<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm2jupbhh.css';
import '../../css/a/acmio-sok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm2jupbhh"/><path class="acmio-sok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-x-48-bold" /></template>

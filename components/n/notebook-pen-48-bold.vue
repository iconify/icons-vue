<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxyn2mbuu.css';
import '../../css/l/l5s4u6bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jxyn2mbuu"/><path class="l5s4u6bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:notebook-pen-48-bold" /></template>

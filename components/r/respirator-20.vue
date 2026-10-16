<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz333ohex.css';
import '../../css/t/tavztwb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mz333ohex"/><path class="tavztwb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:respirator-20" /></template>

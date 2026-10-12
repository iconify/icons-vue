<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt31cubbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jt31cubbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-root-48-bold" /></template>

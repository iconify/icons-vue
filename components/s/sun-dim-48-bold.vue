<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj_1-1b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oj_1-1b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-dim-48-bold" /></template>

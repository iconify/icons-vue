<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed2wdwblh.css';
import '../../css/y/y2dquhbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ed2wdwblh"/><path class="y2dquhbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-cw-48-bold" /></template>

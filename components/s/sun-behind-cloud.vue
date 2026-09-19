<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7mkmzx2k.css';
import '../../css/m/m8d-e8bsi.css';
import '../../css/w/wk2dpgb6q.css';
import '../../css/k/kogb1zhoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h7mkmzx2k"/><path class="m8d-e8bsi"/><path class="wk2dpgb6q"/><path class="kogb1zhoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:sun-behind-cloud" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecm4zwbye.css';
import '../../css/i/i23hwnb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ecm4zwbye"/><path class="i23hwnb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tablet-48-bold" /></template>

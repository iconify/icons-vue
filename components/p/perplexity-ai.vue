<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v331ncoop.css';
import '../../css/o/oe6jpabdk.css';
import '../../css/x/xy26lsb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v331ncoop"/><path class="oe6jpabdk"/><path class="xy26lsb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:perplexity-ai" /></template>

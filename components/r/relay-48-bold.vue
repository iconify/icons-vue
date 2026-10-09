<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4j2f0pva.css';
import '../../css/w/wegshrb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4j2f0pva"/><path class="wegshrb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:relay-48-bold" /></template>

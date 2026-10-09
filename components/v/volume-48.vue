<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9bzs8odx.css';
import '../../css/i/ijrn25w1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r9bzs8odx"/><path class="ijrn25w1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-48" /></template>

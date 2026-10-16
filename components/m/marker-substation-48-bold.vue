<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etlms99xu.css';
import '../../css/k/kd9hivzqs.css';
import '../../css/a/ay7-wge4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="kd9hivzqs"/><path class="ay7-wge4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-substation-48-bold" /></template>

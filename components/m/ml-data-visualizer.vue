<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhsmtt9-j.css';
import '../../css/f/f_0sarbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qhsmtt9-j"/><path class="f_0sarbla ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ml-data-visualizer" /></template>

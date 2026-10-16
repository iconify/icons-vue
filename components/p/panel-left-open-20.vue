<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgiazbbrf.css';
import '../../css/s/sf7om5bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qgiazbbrf"/><path class="sf7om5bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-open-20" /></template>

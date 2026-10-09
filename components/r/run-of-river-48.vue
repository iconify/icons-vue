<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1nb12b5u.css';
import '../../css/e/en62kpb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1nb12b5u"/><path class="en62kpb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:run-of-river-48" /></template>

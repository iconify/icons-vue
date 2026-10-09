<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grk1onbae.css';
import '../../css/x/x7xzn4n0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grk1onbae"/><path class="x7xzn4n0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mouse-48" /></template>

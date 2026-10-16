<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9xbwubme.css';
import '../../css/r/rjepksb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9xbwubme"/><path class="rjepksb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-high-48" /></template>

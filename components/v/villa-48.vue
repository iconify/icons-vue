<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kixdt2b5z.css';
import '../../css/q/qwnitvbfh.css';
import '../../css/r/r2evrhb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kixdt2b5z"/><path class="qwnitvbfh"/><path class="r2evrhb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:villa-48" /></template>

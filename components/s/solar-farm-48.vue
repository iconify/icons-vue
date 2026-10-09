<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1xv4fk9e.css';
import '../../css/k/kf0yeki3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a1xv4fk9e"/><path class="kf0yeki3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-48" /></template>

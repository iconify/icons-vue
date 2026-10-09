<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qusqtbbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qusqtbbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-horizontal-48" /></template>

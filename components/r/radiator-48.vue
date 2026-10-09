<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8wvi4bxf.css';
import '../../css/q/qosg0qauw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8wvi4bxf"/><path class="qosg0qauw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiator-48" /></template>

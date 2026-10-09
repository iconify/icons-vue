<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8div7b-m.css';
import '../../css/p/placboblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8div7b-m"/><path class="placboblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soda-can-48" /></template>

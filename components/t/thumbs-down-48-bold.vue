<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqif18inc.css';
import '../../css/u/u2-y_cc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oqif18inc"/><path class="u2-y_cc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thumbs-down-48-bold" /></template>

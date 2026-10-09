<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01eto0we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h01eto0we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-48" /></template>

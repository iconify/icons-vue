<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01eto0we.css';
import '../../css/w/wlja3wbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h01eto0we"/><path class="wlja3wbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-check-48" /></template>

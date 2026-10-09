<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcp6u-oop.css';
import '../../css/e/ee8dj_rhy.css';
import '../../css/o/on5c6nbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qcp6u-oop"/><path class="ee8dj_rhy"/><path class="on5c6nbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-down-48-bold" /></template>

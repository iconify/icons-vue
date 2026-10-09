<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-xqmce0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-xqmce0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pause-48" /></template>

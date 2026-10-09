<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6otzvulu.css';
import '../../css/g/gczovap1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h6otzvulu"/><path class="gczovap1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-search-48" /></template>

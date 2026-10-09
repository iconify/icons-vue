<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b97769rea.css';
import '../../css/n/nssl3jbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b97769rea"/><path class="nssl3jbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-asc-48-bold" /></template>

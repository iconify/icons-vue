<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htnff4qbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="htnff4qbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sorcerer-hat" /></template>

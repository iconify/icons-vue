<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfo1oe55t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jfo1oe55t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:thin" /></template>

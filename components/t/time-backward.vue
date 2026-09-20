<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu5aiccfe.css';
import '../../css/r/r0zr1abhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nu5aiccfe"/><path class="r0zr1abhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:time-backward" /></template>

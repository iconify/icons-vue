<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8li1cb6w.css';
import '../../css/j/jhuinh89q.css';
import '../../css/l/lu352gbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n8li1cb6w"/><path class="jhuinh89q"/><path class="lu352gbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:stopwatch" /></template>

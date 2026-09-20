<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6fsplbwz.css';
import '../../css/l/l27lvlbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p6fsplbwz"/><path class="l27lvlbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:timer" /></template>

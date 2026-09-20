<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcvlmeb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcvlmeb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:shift" /></template>

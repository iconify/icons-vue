<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7thvyevl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q7thvyevl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tasks" /></template>

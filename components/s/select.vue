<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ra17bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i9ra17bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:select" /></template>

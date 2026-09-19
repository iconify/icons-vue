<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-b4wo2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ok-b4wo2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rocket-fill-16" /></template>

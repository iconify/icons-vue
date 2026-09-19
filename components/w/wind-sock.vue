<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh-kgyh0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rh-kgyh0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:wind-sock" /></template>

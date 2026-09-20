<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9aoccb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9aoccb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:save-solid" /></template>

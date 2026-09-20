<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih9_-c6ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":192};
const content = `<path class="ih9_-c6ca x19hqcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:threads-dark" /></template>
